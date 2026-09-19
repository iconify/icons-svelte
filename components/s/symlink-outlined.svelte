<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uk4jgzb_e.css';
import '../../css/h/hdloyab2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uk4jgzb_e"/><path class="hdloyab2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:symlink-outlined" {...props}></Icon>
