<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqt8a942q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqt8a942q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:slack" {...props}></Icon>
