<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akpibvbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akpibvbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tablet-button-fill-round" {...props}></Icon>
