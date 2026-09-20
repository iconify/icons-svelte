<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sd5_95y7u.css';
import '../../css/w/wqbd_ktkq.css';
import '../../css/s/svb95kb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sd5_95y7u"/><path class="wqbd_ktkq"/><path class="svb95kb8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:tag-hot-price" {...props}></Icon>
