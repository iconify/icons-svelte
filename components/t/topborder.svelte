<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owsd48blx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":960};
const content = `<path class="owsd48blx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:topborder" {...props}></Icon>
