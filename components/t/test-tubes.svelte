<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tigx9-xcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tigx9-xcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:test-tubes" {...props}></Icon>
