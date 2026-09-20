<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to42jfb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="to42jfb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:triangle-solid" {...props}></Icon>
