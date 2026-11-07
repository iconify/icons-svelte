<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-9z98bit.css';
import '../../css/p/pepyl3vpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-9z98bit"/><path class="pepyl3vpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-2-bold-duotone" {...props}></Icon>
