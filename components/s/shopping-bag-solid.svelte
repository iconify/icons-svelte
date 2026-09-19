<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_fo7cb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a_fo7cb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:shopping-bag-solid" {...props}></Icon>
