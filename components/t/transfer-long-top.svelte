<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhq33bcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhq33bcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:transfer-long-top" {...props}></Icon>
