<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-dvcfb3w.css';
import '../../css/f/fcilczb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-dvcfb3w"/><path class="fcilczb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:subscriptions-created-outlined" {...props}></Icon>
