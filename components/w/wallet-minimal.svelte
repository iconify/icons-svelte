<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbq_-nbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbq_-nbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wallet-minimal" {...props}></Icon>
