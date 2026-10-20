<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjagb0hmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjagb0hmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:triangle" {...props}></Icon>
