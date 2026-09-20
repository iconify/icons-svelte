<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp88opbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bp88opbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:snooze-weekend" {...props}></Icon>
