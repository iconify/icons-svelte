<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bey0n9euq.css';
import '../../css/b/bh5yu-cer.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bey0n9euq"/><path class="bh5yu-cer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-visible-filled" {...props}></Icon>
