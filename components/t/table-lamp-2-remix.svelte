<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkytetsie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nkytetsie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:table-lamp-2-remix" {...props}></Icon>
