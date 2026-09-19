<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvh-a_b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvh-a_b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shopping-bag-check" {...props}></Icon>
