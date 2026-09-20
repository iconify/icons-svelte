<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iefwlelij.css';
import '../../css/h/h7exl5bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iefwlelij"/><path class="h7exl5bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:social-rewards-like-circle" {...props}></Icon>
