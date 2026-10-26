<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg2o60bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tg2o60bfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:virus-alt-24px" {...props}></Icon>
