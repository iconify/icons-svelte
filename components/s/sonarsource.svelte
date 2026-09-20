<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quthzcr1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quthzcr1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:sonarsource" {...props}></Icon>
