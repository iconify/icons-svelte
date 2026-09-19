<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhmipyblw.css';
import '../../css/v/vztvh8bnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="qhmipyblw"/><path class="vztvh8bnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-google-plus" {...props}></Icon>
