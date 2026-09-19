<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idzswcbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idzswcbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tick-double-02" {...props}></Icon>
