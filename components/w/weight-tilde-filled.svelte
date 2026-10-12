<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzfod5zsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jzfod5zsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:weight-tilde-filled" {...props}></Icon>
