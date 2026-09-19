<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sq-n_37ce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sq-n_37ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:text-underline" {...props}></Icon>
