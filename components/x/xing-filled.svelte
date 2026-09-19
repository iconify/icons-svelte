<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w85_snbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w85_snbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:xing-filled" {...props}></Icon>
