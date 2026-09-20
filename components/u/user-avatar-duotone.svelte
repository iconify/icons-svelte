<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5v__0v2h.css';
import '../../css/y/y6k8bq-ll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5v__0v2h"/><path class="y6k8bq-ll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:user-avatar-duotone" {...props}></Icon>
