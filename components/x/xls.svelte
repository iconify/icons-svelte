<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7sp1vb4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7sp1vb4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:xls" {...props}></Icon>
