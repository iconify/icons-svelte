<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4gg4hqmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4gg4hqmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:signpost" {...props}></Icon>
