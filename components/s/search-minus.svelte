<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9o_ddbmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9o_ddbmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:search-minus" {...props}></Icon>
