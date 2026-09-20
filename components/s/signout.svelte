<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znayi4bdb.css';
import '../../css/g/g8dz_qbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="znayi4bdb"/><path class="g8dz_qbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:signout" {...props}></Icon>
