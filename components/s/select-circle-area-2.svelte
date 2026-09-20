<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c71na2-8o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c71na2-8o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:select-circle-area-2" {...props}></Icon>
