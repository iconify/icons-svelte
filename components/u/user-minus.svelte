<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo9fkpbzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo9fkpbzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-minus" {...props}></Icon>
