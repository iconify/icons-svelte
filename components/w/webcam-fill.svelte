<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zoorgtbar.css';
import '../../css/k/ks42vwnso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zoorgtbar"/><path clip-rule="evenodd" class="ks42vwnso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:webcam-fill" {...props}></Icon>
