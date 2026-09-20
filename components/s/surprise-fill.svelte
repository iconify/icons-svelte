<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7nf_hb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7nf_hb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:surprise-fill" {...props}></Icon>
