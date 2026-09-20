<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1t7cdk1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h1t7cdk1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:stars-2-outline" {...props}></Icon>
