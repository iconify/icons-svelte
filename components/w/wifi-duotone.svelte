<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubvwb8k9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary ubvwb8k9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:wifi-duotone" {...props}></Icon>
