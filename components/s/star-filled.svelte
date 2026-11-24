<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng1gb-b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ng1gb-b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-filled" {...props}></Icon>
