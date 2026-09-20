<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r34_82_yy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r34_82_yy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:undo-2" {...props}></Icon>
