<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjr12o5iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjr12o5iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:user" {...props}></Icon>
