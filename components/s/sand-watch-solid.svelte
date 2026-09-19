<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3fu9pp5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c3fu9pp5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:sand-watch-solid" {...props}></Icon>
