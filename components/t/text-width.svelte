<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5bw_15rv.css';
import '../../css/u/ud4vqp_ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b5bw_15rv"/><path class="ud4vqp_ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:text-width" {...props}></Icon>
