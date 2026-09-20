<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9a21gb4v.css';
import '../../css/y/y5y8shbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="w9a21gb4v"/><path class="y5y8shbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:waiting-area" {...props}></Icon>
