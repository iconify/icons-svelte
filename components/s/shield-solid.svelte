<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9m7zgb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g9m7zgb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shield-solid" {...props}></Icon>
