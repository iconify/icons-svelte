<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4uiwqbnk.css';
import '../../css/i/it_a7iblf.css';
import '../../css/z/z1wf33p3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b4uiwqbnk"/><path class="it_a7iblf"/><path class="z1wf33p3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:transportation-motorcycle" {...props}></Icon>
