<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmrndwx7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-3,"top":-1.5};
const content = `<path class="kmrndwx7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:transgender" {...props}></Icon>
