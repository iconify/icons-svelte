<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw_njbb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw_njbb5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:shield-x-mark" {...props}></Icon>
