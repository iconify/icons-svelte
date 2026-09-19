<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-4nfubdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-4nfubdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:skip-previous" {...props}></Icon>
