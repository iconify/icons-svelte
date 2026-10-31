<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlsrw1b-f.css';
import '../../css/l/lmk6h0bvk.css';
import '../../css/m/m8y_5gyeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="qlsrw1b-f"/><path class="lmk6h0bvk"/><path class="m8y_5gyeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:thailand" {...props}></Icon>
