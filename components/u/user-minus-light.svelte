<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_ckmhbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_ckmhbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-minus-light" {...props}></Icon>
