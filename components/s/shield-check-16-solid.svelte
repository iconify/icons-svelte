<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp50m7tvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tp50m7tvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:shield-check-16-solid" {...props}></Icon>
