<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9sf_nobs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":200,"height":200};
const content = `<path class="d9sf_nobs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:stylus" {...props}></Icon>
