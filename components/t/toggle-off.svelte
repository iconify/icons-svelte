<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zml8k9bja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zml8k9bja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:toggle-off" {...props}></Icon>
