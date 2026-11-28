<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmy194hqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jmy194hqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:users-info" {...props}></Icon>
