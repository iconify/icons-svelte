<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmhsyhfhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmhsyhfhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:satoshi-v3-outline" {...props}></Icon>
