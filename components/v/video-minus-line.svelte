<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kek9facoo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kek9facoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:video-minus-line" {...props}></Icon>
