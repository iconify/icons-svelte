<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evn_o6jvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evn_o6jvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:row-remove" {...props}></Icon>
