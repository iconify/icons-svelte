<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eibdgkb_a.css';
import '../../css/b/bk8xu6baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eibdgkb_a"/><path class="bk8xu6baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:wlkn" {...props}></Icon>
