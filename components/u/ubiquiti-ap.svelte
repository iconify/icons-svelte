<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyx9xhn2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyx9xhn2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ubiquiti-ap" {...props}></Icon>
