<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht9k5ib0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ht9k5ib0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:van-filled" {...props}></Icon>
