<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-pjibzbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-pjibzbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:user-shared-fill" {...props}></Icon>
