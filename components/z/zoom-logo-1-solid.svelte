<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b351edb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b351edb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:zoom-logo-1-solid" {...props}></Icon>
