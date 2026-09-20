<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e91abccpm.css';
import '../../css/b/bacg9dj7f.css';
import '../../css/x/x792okb-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e91abccpm"/><path class="bacg9dj7f"/><path class="x792okb-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:send-email" {...props}></Icon>
