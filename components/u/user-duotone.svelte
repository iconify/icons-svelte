<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf1wx9bka.css';
import '../../css/c/czb0pkb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="pf1wx9bka"/><path clip-rule="evenodd" class="czb0pkb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:user-duotone" {...props}></Icon>
