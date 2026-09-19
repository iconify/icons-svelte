<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q54x8h4qo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q54x8h4qo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:trash-simple" {...props}></Icon>
