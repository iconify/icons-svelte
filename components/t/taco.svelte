<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h80q1pbzw.css';
import '../../css/a/a-pyxqjuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h80q1pbzw"/><path class="a-pyxqjuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:taco" {...props}></Icon>
