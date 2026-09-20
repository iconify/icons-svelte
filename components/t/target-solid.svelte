<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0yw49byf.css';
import '../../css/u/u-9mz-bzz.css';
import '../../css/f/fydwzq94k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f0yw49byf"/><path clip-rule="evenodd" class="u-9mz-bzz"/><path clip-rule="evenodd" class="fydwzq94k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:target-solid" {...props}></Icon>
