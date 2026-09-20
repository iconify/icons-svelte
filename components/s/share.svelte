<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5fnqw0dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5fnqw0dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:share" {...props}></Icon>
