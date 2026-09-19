<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbtl_1ezz.css';
import '../../css/y/y6c1hc4nj.css';
import '../../css/n/ns9a12iaq.css';
import '../../css/z/zm-9z7rwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="pbtl_1ezz"/><path class="y6c1hc4nj"/><path class="ns9a12iaq"/><path class="zm-9z7rwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:vuetify" {...props}></Icon>
