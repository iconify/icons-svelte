<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxgckcb1c.css';
import '../../css/w/w8tdd6b3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxgckcb1c"/><path class="w8tdd6b3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:subscription-management" {...props}></Icon>
