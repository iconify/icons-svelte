<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjx4p748a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjx4p748a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:undo-solid" {...props}></Icon>
