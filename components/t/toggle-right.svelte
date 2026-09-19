<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vooho20fj.css';
import '../../css/v/vi0k319by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vooho20fj"/><path class="vi0k319by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:toggle-right" {...props}></Icon>
