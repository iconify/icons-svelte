<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0b6dl7uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="d0b6dl7uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:time-one-filled" {...props}></Icon>
