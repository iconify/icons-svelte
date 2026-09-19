<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_184ekvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_184ekvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="feather:umbrella" {...props}></Icon>
