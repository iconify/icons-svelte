<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufkalqu2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ufkalqu2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-plus" {...props}></Icon>
