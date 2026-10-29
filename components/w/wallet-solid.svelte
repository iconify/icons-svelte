<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_qza1oqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o_qza1oqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wallet-solid" {...props}></Icon>
