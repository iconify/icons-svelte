<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp61lbpnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cp61lbpnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:tennis" {...props}></Icon>
