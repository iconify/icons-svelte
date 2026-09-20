<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntsdskbhv.css';
import '../../css/f/fj--vmn1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ntsdskbhv"/><path class="fj--vmn1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:unlock" {...props}></Icon>
