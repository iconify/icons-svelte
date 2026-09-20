<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhzs0bban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhzs0bban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:trends-torch" {...props}></Icon>
