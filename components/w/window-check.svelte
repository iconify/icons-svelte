<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1qak1but.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e1qak1but"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:window-check" {...props}></Icon>
