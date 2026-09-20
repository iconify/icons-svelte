<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lotb4ryqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lotb4ryqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:user-add-filled" {...props}></Icon>
