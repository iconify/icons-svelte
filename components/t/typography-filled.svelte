<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcml5ww9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcml5ww9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:typography-filled" {...props}></Icon>
