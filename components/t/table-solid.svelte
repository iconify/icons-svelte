<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elpkq8vqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="elpkq8vqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:table-solid" {...props}></Icon>
