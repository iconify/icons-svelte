<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2nkf-gjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2nkf-gjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-cancel" {...props}></Icon>
