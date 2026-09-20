<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5zx9_4id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5zx9_4id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:shield" {...props}></Icon>
