<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eda6is5le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eda6is5le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:translate-2-line" {...props}></Icon>
