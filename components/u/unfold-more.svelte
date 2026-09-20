<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fymhyv7jk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fymhyv7jk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:unfold-more" {...props}></Icon>
