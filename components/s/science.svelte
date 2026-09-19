<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn4hvs1rf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sn4hvs1rf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:science" {...props}></Icon>
