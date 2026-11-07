<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liywby_bb.css';
import '../../css/w/wkdbmdblf.css';
import '../../css/l/lc21qzuqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="liywby_bb"/><path class="wkdbmdblf"/><path class="lc21qzuqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-block-bold" {...props}></Icon>
