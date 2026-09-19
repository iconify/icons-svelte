<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl_dgobdx.css';
import '../../css/v/vvtsvebww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="yl_dgobdx"/><path class="vvtsvebww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:social-dropbox" {...props}></Icon>
