<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-cnhtb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-7};
const content = `<path class="s-cnhtb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:unordered-list" {...props}></Icon>
