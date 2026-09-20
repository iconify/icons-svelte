<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uig_arbat.css';
import '../../css/p/p-744obuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uig_arbat"/><path class="p-744obuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:setting-line-duotone-line" {...props}></Icon>
