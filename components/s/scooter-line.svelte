<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8-nzs1vv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8-nzs1vv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:scooter-line" {...props}></Icon>
