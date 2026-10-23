<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot0oobcet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ot0oobcet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:settings-2" {...props}></Icon>
