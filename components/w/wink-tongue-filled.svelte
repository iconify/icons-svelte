<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hcj_ausiv.css';
import '../../css/h/hmp_1pb5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hcj_ausiv"/><path class="hmp_1pb5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wink-tongue-filled" {...props}></Icon>
