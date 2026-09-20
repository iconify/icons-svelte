<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_ny91lky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_ny91lky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:text-box-remove-outline" {...props}></Icon>
