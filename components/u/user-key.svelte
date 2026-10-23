<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1__oqeqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1__oqeqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:user-key" {...props}></Icon>
