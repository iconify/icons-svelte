<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1jspgbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="s1jspgbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:snooze-remix" {...props}></Icon>
