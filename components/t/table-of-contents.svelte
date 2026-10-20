<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kk0od7ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kk0od7ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:table-of-contents" {...props}></Icon>
