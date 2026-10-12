<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yenqbtb5g.css';
import '../../css/e/e_r9uibzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yenqbtb5g"/><path class="e_r9uibzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-check-filled" {...props}></Icon>
