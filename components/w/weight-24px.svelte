<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poq_cbc-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poq_cbc-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:weight-24px" {...props}></Icon>
