<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k_1nlibzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k_1nlibzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:switch-fill" {...props}></Icon>
