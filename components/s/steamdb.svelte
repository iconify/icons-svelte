<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcyq2mbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcyq2mbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:steamdb" {...props}></Icon>
