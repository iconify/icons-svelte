<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-yytbcki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t-yytbcki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:towel" {...props}></Icon>
