<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntqwcibqp.css';
import '../../css/f/fk05w0vld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntqwcibqp"/><path class="fk05w0vld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:users-round-filled" {...props}></Icon>
