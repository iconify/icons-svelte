<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9l6ipbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o9l6ipbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:tesla" {...props}></Icon>
