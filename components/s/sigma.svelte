<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcqo_kb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bcqo_kb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:sigma" {...props}></Icon>
