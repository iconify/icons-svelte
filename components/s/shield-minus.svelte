<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbr5wny1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cbr5wny1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:shield-minus" {...props}></Icon>
