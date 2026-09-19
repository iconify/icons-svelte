<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwnuy0bru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fwnuy0bru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:unhealthy-food-24px" {...props}></Icon>
