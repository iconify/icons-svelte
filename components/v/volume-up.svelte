<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9n_wft3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9n_wft3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:volume-up" {...props}></Icon>
