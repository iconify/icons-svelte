<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7o6v4tnd.css';
import '../../css/r/rargr9bqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j7o6v4tnd"/><path class="rargr9bqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:trending-up-48-bold" {...props}></Icon>
